<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o31igvbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="o31igvbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:prometheus" {...props}></Icon>
