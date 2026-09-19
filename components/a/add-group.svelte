<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maf4ygb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="maf4ygb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:add-group" {...props}></Icon>
