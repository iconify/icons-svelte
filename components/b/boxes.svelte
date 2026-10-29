<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/y6iojqb3m.css';
import '../../css/r/r81zoppqz.css';
import '../../css/w/w2-237bxg.css';
import '../../css/p/pdzxnyjvp.css';
import '../../css/c/c2th96roa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="y6iojqb3m"/><path class="r81zoppqz"/><path class="w2-237bxg wm-a"/><path class="pdzxnyjvp"/><path class="c2th96roa wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:boxes" {...props}></Icon>
