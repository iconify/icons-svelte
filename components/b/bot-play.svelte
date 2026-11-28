<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-tn56vsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-tn56vsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bot-play" {...props}></Icon>
