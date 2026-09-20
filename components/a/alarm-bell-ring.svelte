<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5hc4szqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5hc4szqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:alarm-bell-ring" {...props}></Icon>
