<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3k3xebqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="e3k3xebqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:codeberg" {...props}></Icon>
