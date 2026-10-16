<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1w3r8bvp.css';
import '../../css/j/je2jee5cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z1w3r8bvp"/><path class="je2jee5cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:respirator-48" {...props}></Icon>
