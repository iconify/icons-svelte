<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pipcubbph.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zbtgqfi7q.css';
import '../../css/e/eknai5olh.css';
import '../../css/i/i8imsdbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pipcubbph secondary"/><g class="dt0cm9dhy primary"><path class="zbtgqfi7q"/><path class="eknai5olh"/><path class="i8imsdbhb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:lamp-floor-duo" {...props}></Icon>
