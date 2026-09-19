<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtwq637wt.css';
import '../../css/r/rbu9ceb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rtwq637wt"/><path class="rbu9ceb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:okta" {...props}></Icon>
