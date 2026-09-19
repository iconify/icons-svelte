<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydl97abvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ydl97abvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:bomb" {...props}></Icon>
