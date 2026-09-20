<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn7k6nzcn.css';
import '../../css/c/cpuhaibpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn7k6nzcn"/><path class="cpuhaibpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cronos" {...props}></Icon>
