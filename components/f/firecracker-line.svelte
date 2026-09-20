<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn82cebbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn82cebbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:firecracker-line" {...props}></Icon>
