<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zccxc2biv.css';
import '../../css/f/fcqp69bgt.css';
import '../../css/p/pf9cqzq4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="zccxc2biv"/><path class="fcqp69bgt wm-a"/><path class="pf9cqzq4q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:laptop-duo" {...props}></Icon>
