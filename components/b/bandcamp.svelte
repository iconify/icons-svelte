<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lctjxf-_e.css';
import '../../css/f/fjc_j-bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lctjxf-_e"/><path class="fjc_j-bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bandcamp" {...props}></Icon>
