<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_2b0vb0m.css';
import '../../css/j/j3pf-l97n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_2b0vb0m"/><circle class="j3pf-l97n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:pizza" {...props}></Icon>
