<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_021rz3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_021rz3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:canton-tower-line" {...props}></Icon>
