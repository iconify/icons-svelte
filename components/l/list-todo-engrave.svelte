<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zkftu-bdd.css';
import '../../css/l/ln-u4tuvh.css';
import '../../css/c/cm25f5b_t.css';
import '../../css/b/b2_xccbks.css';
import '../../css/f/fyx95nbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k zkftu-bdd"/><path class="ln-u4tuvh wm-a"/><path class="cm25f5b_t wm-shadow"/><path class="b2_xccbks wm-k"/><path class="fyx95nbgx wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:list-todo-engrave" {...props}></Icon>
