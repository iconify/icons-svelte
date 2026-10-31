<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jigqf2ipl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jigqf2ipl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:package-download-corner-fill-round" {...props}></Icon>
