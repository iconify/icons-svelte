<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpy08yb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpy08yb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-h1-dimmer" {...props}></Icon>
