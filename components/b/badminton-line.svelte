<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4-38zb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4-38zb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badminton-line" {...props}></Icon>
