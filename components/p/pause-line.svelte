<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip62cpo7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ip62cpo7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pause-line" {...props}></Icon>
