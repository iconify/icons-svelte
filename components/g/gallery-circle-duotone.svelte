<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jago5qb8n.css';
import '../../css/z/zwb14lhyy.css';
import '../../css/d/daz1012ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jago5qb8n"/><path class="zwb14lhyy"/><path clip-rule="evenodd" class="daz1012ly"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gallery-circle-duotone" {...props}></Icon>
