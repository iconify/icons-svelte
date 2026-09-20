<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et3dy0ben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="et3dy0ben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-2-ai-line" {...props}></Icon>
