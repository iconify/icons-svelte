<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdu2180en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdu2180en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:receipt-sharp" {...props}></Icon>
