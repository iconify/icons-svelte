<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfqch5byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfqch5byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:message-text" {...props}></Icon>
