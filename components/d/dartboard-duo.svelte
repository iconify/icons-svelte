<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvf4uib1q.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/yszc66b-y.css';
import '../../css/m/mt7e0acqo.css';
import '../../css/t/t7oaa3cbh.css';
import '../../css/m/mmgaxbcck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary yvf4uib1q"/><g class="dt0cm9dhy primary"><path class="yszc66b-y"/><path class="mt7e0acqo"/><path class="t7oaa3cbh"/><path class="mmgaxbcck"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dartboard-duo" {...props}></Icon>
