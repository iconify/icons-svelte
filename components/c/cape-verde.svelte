<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c85pd_b_f.css';
import '../../css/m/mu9as98bc.css';
import '../../css/m/mpcblwabv.css';
import '../../css/u/u5qijbbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="c85pd_b_f"/><path class="mu9as98bc"/><path class="mpcblwabv"/><path class="u5qijbbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:cape-verde" {...props}></Icon>
