<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onux0z-vm.css';
import '../../css/f/f5m_ylwro.css';
import '../../css/v/vvusakkjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="onux0z-vm"/><path class="f5m_ylwro"/><path class="vvusakkjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:emissions-down-20-bold" {...props}></Icon>
