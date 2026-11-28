<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7xarkbwg.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/detamnbsk.css';
import '../../css/h/hw4x0eb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7xarkbwg secondary"/><g class="dt0cm9dhy primary"><path class="detamnbsk"/><path class="hw4x0eb1n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:clover-duo" {...props}></Icon>
