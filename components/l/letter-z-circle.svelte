<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii6adt7xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii6adt7xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-z-circle" {...props}></Icon>
