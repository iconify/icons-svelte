<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbzto1kyu.css';
import '../../css/x/xi_mxdbjk.css';
import '../../css/q/qsvzrh2pz.css';
import '../../css/i/itkht4b8h.css';
import '../../css/p/pf7v6zb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tbzto1kyu"/><path class="xi_mxdbjk"/><path class="qsvzrh2pz"/><path class="itkht4b8h"/><path class="pf7v6zb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gameboy-outline" {...props}></Icon>
