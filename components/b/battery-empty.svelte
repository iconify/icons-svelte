<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqpyn9bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqpyn9bia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:battery-empty" {...props}></Icon>
