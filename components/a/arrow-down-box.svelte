<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltk4xvbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltk4xvbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-down-box" {...props}></Icon>
