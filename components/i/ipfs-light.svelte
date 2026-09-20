<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlba2bbpu.css';
import '../../css/f/fc1chxb1r.css';
import '../../css/z/zlnuk-krx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nlba2bbpu"/><path class="fc1chxb1r"/><path class="zlnuk-krx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ipfs-light" {...props}></Icon>
