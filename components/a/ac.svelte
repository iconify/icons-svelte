<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-vxa4b5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-vxa4b5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:ac" {...props}></Icon>
