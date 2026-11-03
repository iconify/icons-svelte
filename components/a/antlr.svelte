<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx9ys1boa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jx9ys1boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:antlr" {...props}></Icon>
