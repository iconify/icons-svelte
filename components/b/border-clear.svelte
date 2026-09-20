<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl72n8d-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl72n8d-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:border-clear" {...props}></Icon>
