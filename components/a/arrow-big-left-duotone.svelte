<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk43z12xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary xk43z12xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-big-left-duotone" {...props}></Icon>
