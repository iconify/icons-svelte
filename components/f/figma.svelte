<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4028-b3r.css';
import '../../css/t/t5s8-fwfl.css';
import '../../css/a/a6rpd8c1i.css';
import '../../css/d/dyerjlb6g.css';
import '../../css/b/bcl51zb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="i4028-b3r"/><path class="t5s8-fwfl"/><path class="a6rpd8c1i"/><path class="dyerjlb6g"/><path class="bcl51zb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:figma" {...props}></Icon>
