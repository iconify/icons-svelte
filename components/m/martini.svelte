<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/ia0ainb7h.css';
import '../../css/p/pu4i0cblx.css';
import '../../css/j/jsa_ui-gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ia0ainb7h"/><path class="pu4i0cblx"/><path class="jsa_ui-gx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:martini" {...props}></Icon>
