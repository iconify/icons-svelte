<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9q1n_b5d.css';
import '../../css/a/abljxkb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="p9q1n_b5d"/><path class="abljxkb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:haskell" {...props}></Icon>
