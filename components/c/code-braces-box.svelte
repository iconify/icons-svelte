<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7qpof6pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7qpof6pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:code-braces-box" {...props}></Icon>
