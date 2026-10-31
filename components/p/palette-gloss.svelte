<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-pi8n4vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-pi8n4vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:palette-gloss" {...props}></Icon>
