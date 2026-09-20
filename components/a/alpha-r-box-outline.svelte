<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6h-m2bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6h-m2bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-r-box-outline" {...props}></Icon>
