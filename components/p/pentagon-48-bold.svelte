<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8frtckyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p8frtckyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pentagon-48-bold" {...props}></Icon>
