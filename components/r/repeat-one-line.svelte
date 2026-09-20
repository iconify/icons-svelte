<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us81xcbgt.css';
import '../../css/w/wpm7l0iir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us81xcbgt"/><path class="wpm7l0iir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:repeat-one-line" {...props}></Icon>
