<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9sia4b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w9sia4b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:adjustments-vertical-16-solid" {...props}></Icon>
