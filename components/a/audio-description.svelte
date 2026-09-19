<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tygts_5js.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tygts_5js"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:audio-description" {...props}></Icon>
