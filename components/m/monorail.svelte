<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz1map5pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xz1map5pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:monorail" {...props}></Icon>
