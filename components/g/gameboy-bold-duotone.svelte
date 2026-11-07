<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivpr48ban.css';
import '../../css/m/mkzpafxuf.css';
import '../../css/x/xi_mxdbjk.css';
import '../../css/q/qsvzrh2pz.css';
import '../../css/h/hf_mynhto.css';
import '../../css/p/pf7v6zb-s.css';
import '../../css/a/an4daob8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivpr48ban"/><path class="mkzpafxuf"/><path class="xi_mxdbjk"/><path class="qsvzrh2pz"/><path class="hf_mynhto"/><path class="pf7v6zb-s"/><path class="an4daob8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gameboy-bold-duotone" {...props}></Icon>
