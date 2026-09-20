<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7sufsb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7sufsb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-charging-50" {...props}></Icon>
