<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1m5k6buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1m5k6buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:linux-solid" {...props}></Icon>
