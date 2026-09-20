<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfd2lvbyk.css';
import '../../css/q/qfxjj7d4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rfd2lvbyk"/><path class="qfxjj7d4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:music-vinyl-record" {...props}></Icon>
