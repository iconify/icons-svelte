<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wclz1cc_c.css';
import '../../css/c/czevaumet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wclz1cc_c"/><path class="czevaumet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:programming-language-monitor-css-bold" {...props}></Icon>
