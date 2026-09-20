<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytk1r_97s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytk1r_97s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:plus" {...props}></Icon>
