<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gwj2w_bps.css';
import '../../css/q/q7aor7big.css';
import '../../css/c/cehgcdc1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gwj2w_bps"/><path class="q7aor7big"/><path class="cehgcdc1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-storage-line-duotone" {...props}></Icon>
