<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/eywof3n0e.css';
import '../../css/x/xzuqt3brk.css';
import '../../css/j/jk12kbopf.css';
import '../../css/e/e7pe4749l.css';
import '../../css/l/lcpbulbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="eywof3n0e"/><path class="xzuqt3brk"/><path class="jk12kbopf"/><path class="e7pe4749l"/><path class="lcpbulbhy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:move" {...props}></Icon>
