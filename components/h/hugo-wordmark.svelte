<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he1q6_b1l.css';
import '../../css/v/vzzpw72td.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="he1q6_b1l"/><path class="vzzpw72td"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:hugo-wordmark" {...props}></Icon>
