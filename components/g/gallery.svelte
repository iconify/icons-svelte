<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs4r5cb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs4r5cb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:gallery" {...props}></Icon>
