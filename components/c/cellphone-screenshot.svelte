<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp0fyhbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp0fyhbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cellphone-screenshot" {...props}></Icon>
