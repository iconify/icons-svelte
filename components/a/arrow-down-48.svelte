<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df1n7oboy.css';
import '../../css/d/dp3euwb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="df1n7oboy"/><path class="dp3euwb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-down-48" {...props}></Icon>
