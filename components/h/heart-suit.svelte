<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc41vib9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hc41vib9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:heart-suit" {...props}></Icon>
