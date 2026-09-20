<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv1oty2ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv1oty2ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:layout-align-bottom" {...props}></Icon>
