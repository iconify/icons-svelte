<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9sfw7l0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9sfw7l0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moon-sleep-line" {...props}></Icon>
