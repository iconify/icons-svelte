<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6mo4z6eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6mo4z6eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lamp-desk-gloss" {...props}></Icon>
