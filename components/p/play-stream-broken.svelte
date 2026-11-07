<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t_ft9_syu.css';
import '../../css/z/zx4z7abfl.css';
import '../../css/h/hr_fv7unq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t_ft9_syu"/><path class="zx4z7abfl"/><path class="hr_fv7unq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:play-stream-broken" {...props}></Icon>
