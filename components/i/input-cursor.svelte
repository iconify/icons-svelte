<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/z89jkdb_z.css';
import '../../css/j/jqjybu5du.css';
import '../../css/r/rqhxtipmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="z89jkdb_z"/><path class="jqjybu5du"/><path class="rqhxtipmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:input-cursor" {...props}></Icon>
