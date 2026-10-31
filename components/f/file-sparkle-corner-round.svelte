<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svahalbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svahalbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-sparkle-corner-round" {...props}></Icon>
