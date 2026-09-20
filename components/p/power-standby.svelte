<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omd7uhbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="omd7uhbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:power-standby" {...props}></Icon>
