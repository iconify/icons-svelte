<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuj8kqcdw.css';
import '../../css/d/d33yrzbil.css';
import '../../css/l/ls49jcb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuj8kqcdw"/><path class="d33yrzbil"/><path class="ls49jcb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:radio-antenna-handle" {...props}></Icon>
