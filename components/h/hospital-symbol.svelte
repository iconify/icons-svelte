<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktdlfcccj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktdlfcccj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:hospital-symbol" {...props}></Icon>
