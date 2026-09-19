<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qsdfs2b4v.css';
import '../../css/f/fiddms--z.css';
import '../../css/f/fkfuyq4qg.css';
import '../../css/p/p-p9psboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="building-outline"><g class="Vector cuyn6tgcc"><path clip-rule="evenodd" class="qsdfs2b4v"/><path clip-rule="evenodd" class="fiddms--z"/><path clip-rule="evenodd" class="fkfuyq4qg"/><path class="p-p9psboo"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:building-outline" {...props}></Icon>
