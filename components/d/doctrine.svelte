<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u641ht8nk.css';
import '../../css/e/efxthlbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="u641ht8nk"/><path class="efxthlbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:doctrine" {...props}></Icon>
