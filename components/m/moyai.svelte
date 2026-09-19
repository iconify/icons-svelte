<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg9j1xb1g.css';
import '../../css/c/cft1j_bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xg9j1xb1g"/><path class="cft1j_bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:moyai" {...props}></Icon>
