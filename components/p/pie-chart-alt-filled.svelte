<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxjt1bbjd.css';
import '../../css/k/k_ivpjbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxjt1bbjd"/><path class="k_ivpjbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pie-chart-alt-filled" {...props}></Icon>
