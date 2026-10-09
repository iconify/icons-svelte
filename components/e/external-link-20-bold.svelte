<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkira4mse.css';
import '../../css/d/d8zayxbdq.css';
import '../../css/q/q9gdl6bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lkira4mse"/><path class="d8zayxbdq"/><path class="q9gdl6bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:external-link-20-bold" {...props}></Icon>
