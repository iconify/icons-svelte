<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgxn76bkp.css';
import '../../css/g/gf2qt1pqt.css';
import '../../css/a/a71-bmb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="wgxn76bkp"><circle class="gf2qt1pqt"/><path class="a71-bmb9e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:react" {...props}></Icon>
