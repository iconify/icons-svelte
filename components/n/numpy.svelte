<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-peh3beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="s-peh3beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:numpy" {...props}></Icon>
