<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t63efkb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t63efkb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eyedropper-remove" {...props}></Icon>
