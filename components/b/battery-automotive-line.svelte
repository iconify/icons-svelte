<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m310ahvgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m310ahvgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:battery-automotive-line" {...props}></Icon>
