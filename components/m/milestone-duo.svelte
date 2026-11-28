<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnun2klcg.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zdu-dcbfe.css';
import '../../css/f/fon0b9_ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnun2klcg secondary"/><g class="dt0cm9dhy primary"><path class="zdu-dcbfe"/><path class="fon0b9_ly"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:milestone-duo" {...props}></Icon>
