<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/plpbm6b2f.css';
import '../../css/z/zabmlzbvr.css';
import '../../css/w/w9jf0vajj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="plpbm6b2f"/><path clip-rule="evenodd" class="zabmlzbvr"/><path class="w9jf0vajj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:gonorrhea-alt" {...props}></Icon>
