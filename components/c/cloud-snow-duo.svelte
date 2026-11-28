<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msk0mniql.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b66ewmbkg.css';
import '../../css/x/x1q07rbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msk0mniql secondary"/><g class="dt0cm9dhy primary"><path class="b66ewmbkg"/><path class="x1q07rbem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-snow-duo" {...props}></Icon>
