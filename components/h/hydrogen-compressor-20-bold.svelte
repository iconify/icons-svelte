<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itjermisk.css';
import '../../css/a/a7tgj93ph.css';
import '../../css/i/ioz9rd6gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="itjermisk"/><path class="a7tgj93ph"/><path class="ioz9rd6gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-compressor-20-bold" {...props}></Icon>
