<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl344es-n.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/oqqr_m9av.css';
import '../../css/z/ze9vub3ex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl344es-n secondary"/><g class="dt0cm9dhy primary"><path class="oqqr_m9av"/><path class="ze9vub3ex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:panel-bottom-duo" {...props}></Icon>
