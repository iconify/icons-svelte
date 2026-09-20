<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1t-eearw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1t-eearw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:building-sharp" {...props}></Icon>
