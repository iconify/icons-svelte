<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0ow95o1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0ow95o1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-audio-check" {...props}></Icon>
