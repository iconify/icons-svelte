<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh3rjqrag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rh3rjqrag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hot-rock-48" {...props}></Icon>
