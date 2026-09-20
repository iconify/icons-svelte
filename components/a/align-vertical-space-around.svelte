<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe9-bnb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oe9-bnb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-vertical-space-around" {...props}></Icon>
