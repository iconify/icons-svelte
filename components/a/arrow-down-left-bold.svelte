<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fck5xk6ae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fck5xk6ae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-down-left-bold" {...props}></Icon>
