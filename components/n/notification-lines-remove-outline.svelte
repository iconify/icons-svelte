<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjpoj8_cg.css';
import '../../css/a/aso22wbxm.css';
import '../../css/s/sv_kzcbth.css';
import '../../css/l/l0exbachf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjpoj8_cg"/><path class="aso22wbxm"/><path class="sv_kzcbth"/><path class="l0exbachf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notification-lines-remove-outline" {...props}></Icon>
