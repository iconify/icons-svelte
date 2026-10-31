<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-1oyub4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-1oyub4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:coffin-gloss" {...props}></Icon>
