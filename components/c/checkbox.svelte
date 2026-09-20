<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bttzdh-kf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bttzdh-kf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:checkbox" {...props}></Icon>
