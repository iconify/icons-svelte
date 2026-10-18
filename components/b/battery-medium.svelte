<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk4xhy-nc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk4xhy-nc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:battery-medium" {...props}></Icon>
