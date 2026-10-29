<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_-xw2btr.css';
import '../../css/n/nmu8t-fwz.css';
import '../../css/v/vdtxttb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_-xw2btr wm-shadow"/><path class="nmu8t-fwz wm-k"/><path class="vdtxttb4w wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:chevron-down" {...props}></Icon>
