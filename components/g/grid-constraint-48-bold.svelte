<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5ew6wg8k.css';
import '../../css/c/clhq3_b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u5ew6wg8k"/><path class="clhq3_b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grid-constraint-48-bold" {...props}></Icon>
