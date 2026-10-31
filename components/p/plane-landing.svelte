<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/y/y40hbi6qp.css';
import '../../css/g/g12qyt31i.css';
import '../../css/j/j4qps2bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="wm-shadow y40hbi6qp"/><path class="g12qyt31i wm-shadow"/><path class="j4qps2bou"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:plane-landing" {...props}></Icon>
