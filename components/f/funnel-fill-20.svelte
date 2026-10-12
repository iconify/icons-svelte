<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai0frwm-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ai0frwm-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:funnel-fill-20" {...props}></Icon>
