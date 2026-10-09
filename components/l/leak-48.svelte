<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0lt8rbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j0lt8rbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:leak-48" {...props}></Icon>
