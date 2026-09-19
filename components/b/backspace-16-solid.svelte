<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3-d0ybjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j3-d0ybjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:backspace-16-solid" {...props}></Icon>
