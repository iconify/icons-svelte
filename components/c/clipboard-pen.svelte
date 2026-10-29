<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jljkj-bjl.css';
import '../../css/p/p88jhsbpe.css';
import '../../css/j/j10ehyblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="jljkj-bjl"/><path class="p88jhsbpe wm-a"/><path class="j10ehyblf wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:clipboard-pen" {...props}></Icon>
