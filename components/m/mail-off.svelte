<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq_593bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oq_593bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:mail-off" {...props}></Icon>
