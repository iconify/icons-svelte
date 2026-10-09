<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxk-14-gk.css';
import '../../css/r/r58q_lbbh.css';
import '../../css/f/fn2c-okpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fxk-14-gk"/><path class="r58q_lbbh"/><path class="fn2c-okpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cogs-48" {...props}></Icon>
