<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/s/s5s_qk0sn.css';
import '../../css/c/cplpj-rbo.css';
import '../../css/i/icfu2xbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="s5s_qk0sn"/><circle class="cplpj-rbo"/><path class="icfu2xbdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:microphone-one" {...props}></Icon>
