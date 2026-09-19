<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk77iabep.css';
import '../../css/i/it3-pwbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xk77iabep"/><path class="it3-pwbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:jquery-wordmark" {...props}></Icon>
