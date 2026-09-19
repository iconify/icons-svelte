<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyvy0x6vz.css';
import '../../css/n/nh4ls7l6o.css';
import '../../css/f/f_tbp8boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<ellipse class="fyvy0x6vz"/><ellipse class="nh4ls7l6o"/><path class="f_tbp8boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:bicep" {...props}></Icon>
