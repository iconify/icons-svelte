<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0ivrqiku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0ivrqiku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:baseball-2-line" {...props}></Icon>
