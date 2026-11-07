<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn_frcb-c.css';
import '../../css/b/bjuz8i9vl.css';
import '../../css/w/w8znvab1d.css';
import '../../css/a/a5xq_ybez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn_frcb-c"/><path class="bjuz8i9vl"/><path class="w8znvab1d"/><path class="a5xq_ybez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:confounded-square-bold-duotone" {...props}></Icon>
