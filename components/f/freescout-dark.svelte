<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha514kb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":96,"height":96};
const content = `<path class="ha514kb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:freescout-dark" {...props}></Icon>
