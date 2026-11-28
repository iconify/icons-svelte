<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8sf3_bdl.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pb2dl2bib.css';
import '../../css/u/u9u5q7nrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8sf3_bdl secondary"/><g class="dt0cm9dhy primary"><path class="pb2dl2bib"/><path class="u9u5q7nrr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:piggy-bank-duo" {...props}></Icon>
