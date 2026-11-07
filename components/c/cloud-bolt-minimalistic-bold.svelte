<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srdp-xb5r.css';
import '../../css/l/lqidd2bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="srdp-xb5r"/><path class="lqidd2bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-bolt-minimalistic-bold" {...props}></Icon>
