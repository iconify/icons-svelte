<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/c/c12o_4bzm.css';
import '../../css/p/pd3_r0b4h.css';
import '../../css/z/zdoh6ubhg.css';
import '../../css/o/ok9s4-bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path clip-rule="evenodd" class="c12o_4bzm"/><path class="pd3_r0b4h"/><path class="zdoh6ubhg"/><path class="ok9s4-bxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:pesticide" {...props}></Icon>
