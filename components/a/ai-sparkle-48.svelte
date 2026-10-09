<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh2lvo64r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wh2lvo64r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ai-sparkle-48" {...props}></Icon>
