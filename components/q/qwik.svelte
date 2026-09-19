<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovzl77bwj.css';
import '../../css/m/mf1r0nbce.css';
import '../../css/w/wz-tl9bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ovzl77bwj"/><path class="mf1r0nbce"/><path class="wz-tl9bco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:qwik" {...props}></Icon>
