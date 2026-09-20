<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fp56qruxy.css';
import '../../css/q/q5ib2xb9z.css';
import '../../css/x/xyps7cbjg.css';
import '../../css/y/ydwzs1jqt.css';
import '../../css/f/fr-6pqe2i.css';
import '../../css/n/npxsi1bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="fp56qruxy"/><path clip-rule="evenodd" class="q5ib2xb9z"/><path class="xyps7cbjg"/><path class="ydwzs1jqt"/><path class="fr-6pqe2i"/><path clip-rule="evenodd" class="npxsi1bzj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:knive-fork" {...props}></Icon>
