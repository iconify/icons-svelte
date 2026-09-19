<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpfogblvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="bpfogblvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:angle-up" {...props}></Icon>
