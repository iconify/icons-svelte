<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0x_ddciz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0x_ddciz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:credit-card-settings" {...props}></Icon>
