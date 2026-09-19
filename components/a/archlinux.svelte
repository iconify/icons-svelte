<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9seynbrw.css';
import '../../css/b/bz2e_vbhp.css';
import '../../css/c/cq1gd6biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="w9seynbrw"><path class="bz2e_vbhp"/><path class="cq1gd6biw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:archlinux" {...props}></Icon>
