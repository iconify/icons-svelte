<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obf1m3bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="obf1m3bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:arrow-diagonal-bottom-right" {...props}></Icon>
