<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp7x4_pfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="fp7x4_pfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:file-code-o" {...props}></Icon>
