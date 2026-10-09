<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by36c192e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="by36c192e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:maximize-48-bold" {...props}></Icon>
