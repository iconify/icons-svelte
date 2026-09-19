<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4z-3_leu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="q4z-3_leu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:file-pdf-o" {...props}></Icon>
