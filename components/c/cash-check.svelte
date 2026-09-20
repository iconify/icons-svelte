<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybhi4upzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybhi4upzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cash-check" {...props}></Icon>
