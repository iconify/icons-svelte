<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0jwjim7u.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mac0w8brc.css';
import '../../css/i/i0l9gyb3p.css';
import '../../css/z/zrlh-6b7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0jwjim7u secondary"/><g class="dt0cm9dhy primary"><path class="mac0w8brc"/><path class="i0l9gyb3p"/><path class="zrlh-6b7n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:atom-duo" {...props}></Icon>
