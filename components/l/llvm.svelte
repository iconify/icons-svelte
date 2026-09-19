<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om5rb4z9e.css';
import '../../css/h/h62eebccu.css';
import '../../css/f/fj8_lom1v.css';
import '../../css/f/f557nxb9g.css';
import '../../css/y/y9dyeo2-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="om5rb4z9e"/><path class="h62eebccu"/><path class="fj8_lom1v"/><path class="f557nxb9g"/><path class="y9dyeo2-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:llvm" {...props}></Icon>
