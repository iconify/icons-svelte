<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dssydwbjm.css';
import '../../css/u/uzp27665y.css';
import '../../css/z/zp5y05ahx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dssydwbjm"/><path class="uzp27665y"/><path class="zp5y05ahx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oil-tanker-48" {...props}></Icon>
