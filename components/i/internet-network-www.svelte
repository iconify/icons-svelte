<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_gwm_bba.css';
import '../../css/x/xvmas6b-z.css';
import '../../css/o/ois2n1s1o.css';
import '../../css/k/kg_t2pb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k_gwm_bba"/><path class="xvmas6b-z"/><path class="ois2n1s1o"/><path class="kg_t2pb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:internet-network-www" {...props}></Icon>
