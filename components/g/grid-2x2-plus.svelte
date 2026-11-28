<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/iye6zdbmz.css';
import '../../css/c/cfkicbk9n.css';
import '../../css/y/ycawehbdj.css';
import '../../css/o/o49jzbcjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="iye6zdbmz"/><path class="cfkicbk9n"/><path class="ycawehbdj"/><path class="o49jzbcjj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:grid-2x2-plus" {...props}></Icon>
