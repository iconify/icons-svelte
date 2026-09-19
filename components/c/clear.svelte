<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw4_6ch_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gw4_6ch_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:clear" {...props}></Icon>
