<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdo4_sr4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdo4_sr4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:confused" {...props}></Icon>
