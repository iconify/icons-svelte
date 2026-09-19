<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbb50ac0d.css';
import '../../css/a/ax8q1_b6f.css';
import '../../css/w/waw_c6bot.css';
import '../../css/h/hkmfzxban.css';
import '../../css/d/dwqapubbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pbb50ac0d"/><path class="ax8q1_b6f"/><path class="waw_c6bot"/><path class="hkmfzxban"/><path class="dwqapubbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:pixi" {...props}></Icon>
