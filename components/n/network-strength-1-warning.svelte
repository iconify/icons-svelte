<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1jccw92g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1jccw92g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:network-strength-1-warning" {...props}></Icon>
