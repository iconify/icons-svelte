<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt-gwsbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt-gwsbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lasso-select-fill" {...props}></Icon>
