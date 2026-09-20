<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l37npu1fk.css';
import '../../css/s/sp_sykbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l37npu1fk"/><path class="sp_sykbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-rke" {...props}></Icon>
