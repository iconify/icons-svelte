<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl0wk2bre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl0wk2bre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gemini-fill" {...props}></Icon>
