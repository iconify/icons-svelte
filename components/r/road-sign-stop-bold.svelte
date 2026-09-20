<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcutg2b4x.css';
import '../../css/m/m5w08nblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcutg2b4x"/><path class="m5w08nblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:road-sign-stop-bold" {...props}></Icon>
