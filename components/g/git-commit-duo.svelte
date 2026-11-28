<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/felu19btq.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kmaxbibqw.css';
import '../../css/s/sl9j_vb_t.css';
import '../../css/l/l5-q_fbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="felu19btq secondary"/><g class="dt0cm9dhy primary"><path class="kmaxbibqw"/><path class="sl9j_vb_t"/><path class="l5-q_fbxp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:git-commit-duo" {...props}></Icon>
