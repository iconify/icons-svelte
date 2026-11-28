<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiklu-b8j.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tgy8uab8v.css';
import '../../css/g/gzcfjqb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kiklu-b8j secondary"/><g class="dt0cm9dhy primary"><path class="tgy8uab8v"/><path class="gzcfjqb8o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-pen-duo" {...props}></Icon>
