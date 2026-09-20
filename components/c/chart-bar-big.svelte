<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy4qd-b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy4qd-b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-bar-big" {...props}></Icon>
