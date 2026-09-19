<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhxm0b_ck.css';
import '../../css/h/hf_7z-k3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="hhxm0b_ck"/><path class="hf_7z-k3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:ban" {...props}></Icon>
