<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqsnjmbdm.css';
import '../../css/k/kykp8gb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqsnjmbdm"/><path class="kykp8gb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:data" {...props}></Icon>
