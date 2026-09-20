<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6_lwd2sp.css';
import '../../css/e/e-tetgb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6_lwd2sp"/><path class="e-tetgb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:navigation-page-right" {...props}></Icon>
