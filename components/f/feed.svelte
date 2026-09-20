<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnr7fptxp.css';
import '../../css/w/wl2c1p1go.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnr7fptxp"/><path class="wl2c1p1go"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:feed" {...props}></Icon>
