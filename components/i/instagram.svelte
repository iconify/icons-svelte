<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9kyeodza.css';
import '../../css/t/t_0rrslox.css';
import '../../css/w/wxma-tm4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9kyeodza"/><path class="t_0rrslox"/><circle class="wxma-tm4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:instagram" {...props}></Icon>
