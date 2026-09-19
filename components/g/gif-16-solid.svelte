<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogtpobcfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ogtpobcfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:gif-16-solid" {...props}></Icon>
