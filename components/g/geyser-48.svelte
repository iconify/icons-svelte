<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfx3nk7mg.css';
import '../../css/i/i3ymxkbqr.css';
import '../../css/x/x7cirobba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wfx3nk7mg"/><path class="i3ymxkbqr"/><path class="x7cirobba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:geyser-48" {...props}></Icon>
