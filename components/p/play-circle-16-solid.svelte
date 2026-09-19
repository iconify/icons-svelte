<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc0uvflaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dc0uvflaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:play-circle-16-solid" {...props}></Icon>
