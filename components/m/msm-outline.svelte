<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pix9i5bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pix9i5bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:msm-outline" {...props}></Icon>
