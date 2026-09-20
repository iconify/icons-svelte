<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncwy8z9pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncwy8z9pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:factory-sharp" {...props}></Icon>
