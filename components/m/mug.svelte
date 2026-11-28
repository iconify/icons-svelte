<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/delqnrbzm.css';
import '../../css/j/j_fa22bmn.css';
import '../../css/m/mbzmyys3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="delqnrbzm"/><path class="j_fa22bmn"/><path class="mbzmyys3e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mug" {...props}></Icon>
