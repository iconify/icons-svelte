<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzhyhrb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gzhyhrb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:eleventy" {...props}></Icon>
