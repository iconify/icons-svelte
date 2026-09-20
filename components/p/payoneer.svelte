<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txfwdmb_e.css';
import '../../css/s/slra1_f-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txfwdmb_e"/><path clip-rule="evenodd" class="slra1_f-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:payoneer" {...props}></Icon>
