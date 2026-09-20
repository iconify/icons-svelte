<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhxk_vbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lhxk_vbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:double-check" {...props}></Icon>
