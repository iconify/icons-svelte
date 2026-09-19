<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj10p5rzw.css';
import '../../css/b/bmckwmrqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lj10p5rzw"/><path class="bmckwmrqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:open" {...props}></Icon>
