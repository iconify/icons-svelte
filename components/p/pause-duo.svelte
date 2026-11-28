<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr99gxblo.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/cq_0n3bjh.css';
import '../../css/a/agr5fpl-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr99gxblo secondary"/><g class="dt0cm9dhy primary"><path class="cq_0n3bjh"/><path class="agr5fpl-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pause-duo" {...props}></Icon>
