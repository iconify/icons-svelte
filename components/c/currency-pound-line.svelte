<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu55nd1hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu55nd1hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-pound-line" {...props}></Icon>
