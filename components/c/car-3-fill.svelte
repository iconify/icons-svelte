<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9v2a47yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9v2a47yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:car-3-fill" {...props}></Icon>
