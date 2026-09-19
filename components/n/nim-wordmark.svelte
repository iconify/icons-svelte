<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gijyo05ck.css';
import '../../css/l/l0-cexb8m.css';
import '../../css/a/a1k_o6b_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gijyo05ck"/><path class="l0-cexb8m"/><path class="a1k_o6b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nim-wordmark" {...props}></Icon>
