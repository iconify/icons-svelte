<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f63gk40af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="f63gk40af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:poetry" {...props}></Icon>
