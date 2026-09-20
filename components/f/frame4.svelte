<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk8z51b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xk8z51b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:frame4" {...props}></Icon>
