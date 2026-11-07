<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl21u1gxg.css';
import '../../css/m/mhkgzbcsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kl21u1gxg"/><path class="mhkgzbcsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-down-from-line-bold" {...props}></Icon>
