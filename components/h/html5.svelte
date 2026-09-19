<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crhxvtukx.css';
import '../../css/m/m1mw2hbxc.css';
import '../../css/q/q7vfdtbpt.css';
import '../../css/z/z8l5u13up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="crhxvtukx"/><path class="m1mw2hbxc"/><path class="q7vfdtbpt"/><path class="z8l5u13up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:html5" {...props}></Icon>
