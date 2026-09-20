<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b36ds2bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="b36ds2bbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:anomaly-none" {...props}></Icon>
