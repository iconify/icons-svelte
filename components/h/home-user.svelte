<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qq9ymcb2g.css';
import '../../css/a/aq19pqh_t.css';
import '../../css/f/fgetbabxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qq9ymcb2g"/><path clip-rule="evenodd" class="aq19pqh_t"/><path clip-rule="evenodd" class="fgetbabxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:home-user" {...props}></Icon>
