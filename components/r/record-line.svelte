<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg5z4hbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rg5z4hbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:record-line" {...props}></Icon>
