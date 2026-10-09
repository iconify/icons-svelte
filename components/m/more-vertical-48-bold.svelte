<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh0yh6tgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rh0yh6tgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:more-vertical-48-bold" {...props}></Icon>
