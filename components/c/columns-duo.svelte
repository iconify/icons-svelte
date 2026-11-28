<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m666yyb0c.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dytsri-lp.css';
import '../../css/p/pok-skbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m666yyb0c secondary"/><g class="dt0cm9dhy primary"><path class="dytsri-lp"/><path class="pok-skbxv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:columns-duo" {...props}></Icon>
