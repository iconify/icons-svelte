<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5hsqdgum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="p5hsqdgum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:crystal" {...props}></Icon>
