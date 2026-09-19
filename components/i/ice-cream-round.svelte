<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek81er-1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ek81er-1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:ice-cream-round" {...props}></Icon>
