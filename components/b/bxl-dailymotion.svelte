<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2g63cekk.css';
import '../../css/h/hm4-mmydo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2g63cekk"/><path class="hm4-mmydo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-dailymotion" {...props}></Icon>
