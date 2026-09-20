<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fesfmrsef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fesfmrsef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heavy-snowstorm-line" {...props}></Icon>
