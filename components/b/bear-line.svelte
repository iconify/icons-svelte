<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys2xnwm9y.css';
import '../../css/c/cc8xe5byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys2xnwm9y"/><path class="cc8xe5byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bear-line" {...props}></Icon>
