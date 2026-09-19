<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1i5j5zjy.css';
import '../../css/t/tsra2_hxh.css';
import '../../css/n/n6dcl9bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="h1i5j5zjy"/><path class="tsra2_hxh"/><path class="n6dcl9bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:haskell" {...props}></Icon>
