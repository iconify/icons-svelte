<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glxb9obxa.css';
import '../../css/y/yq7ps8ebr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="glxb9obxa"/><path class="yq7ps8ebr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-down-right-48-bold" {...props}></Icon>
