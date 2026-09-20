<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmmi8805w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmmi8805w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:audio-description-2-ai" {...props}></Icon>
