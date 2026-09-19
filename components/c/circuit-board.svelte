<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/n/nol19vq4t.css';
import '../../css/a/a4ys69bct.css';
import '../../css/h/hzapyruls.css';
import '../../css/a/a6walofgz.css';
import '../../css/u/uwl0krnbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="nol19vq4t"/><path class="a4ys69bct"/><circle class="hzapyruls"/><path class="a6walofgz"/><path class="uwl0krnbp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:circuit-board" {...props}></Icon>
