<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw069obaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nw069obaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:chatbot-outline" {...props}></Icon>
