<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpbsadttl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bpbsadttl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cycle-alt" {...props}></Icon>
