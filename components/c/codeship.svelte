<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjq1h0isb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yjq1h0isb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:codeship" {...props}></Icon>
