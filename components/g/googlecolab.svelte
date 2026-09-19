<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2tgebcxx.css';
import '../../css/b/bd3d8z14l.css';
import '../../css/g/gnu68mb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q2tgebcxx"/><path class="bd3d8z14l"/><path class="gnu68mb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:googlecolab" {...props}></Icon>
