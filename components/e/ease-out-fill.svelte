<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq7x_9fin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq7x_9fin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ease-out-fill" {...props}></Icon>
