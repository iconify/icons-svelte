<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxx8nlbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxx8nlbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heartbeat-line" {...props}></Icon>
