<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs_lo7bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="cs_lo7bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:polyline" {...props}></Icon>
