<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws-o9bc6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ws-o9bc6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:lightbulb-fill-12" {...props}></Icon>
