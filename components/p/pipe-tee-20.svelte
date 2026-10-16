<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/supgx2bpn.css';
import '../../css/s/ss4fa8bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="supgx2bpn"/><path class="ss4fa8bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-tee-20" {...props}></Icon>
