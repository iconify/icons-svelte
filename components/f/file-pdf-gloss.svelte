<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2lunc9yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2lunc9yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-pdf-gloss" {...props}></Icon>
