<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz0_wjbxg.css';
import '../../css/a/aeebr_bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sz0_wjbxg"/><path class="aeebr_bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grid-network-48-bold" {...props}></Icon>
