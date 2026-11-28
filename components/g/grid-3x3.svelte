<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mie31z6an.css';
import '../../css/q/qnz8_nike.css';
import '../../css/d/d1akiylgq.css';
import '../../css/y/yg7y56b9u.css';
import '../../css/f/fh5b84bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mie31z6an"/><path class="qnz8_nike"/><path class="d1akiylgq"/><path class="yg7y56b9u"/><path class="fh5b84bbb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:grid-3x3" {...props}></Icon>
