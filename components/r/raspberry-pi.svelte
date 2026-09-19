<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa8ssc4_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xa8ssc4_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:raspberry-pi" {...props}></Icon>
