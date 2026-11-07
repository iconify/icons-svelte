<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c08ckl39y.css';
import '../../css/f/fdtedkyxq.css';
import '../../css/r/re8-x0t_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c08ckl39y"/><path class="fdtedkyxq"/><path class="re8-x0t_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:filters-bold" {...props}></Icon>
