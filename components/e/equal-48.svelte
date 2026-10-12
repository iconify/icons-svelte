<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhk4ll00z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xhk4ll00z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:equal-48" {...props}></Icon>
