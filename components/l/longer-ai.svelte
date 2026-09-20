<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk6nt8u7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk6nt8u7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:longer-ai" {...props}></Icon>
