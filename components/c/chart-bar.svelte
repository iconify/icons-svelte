<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh-7cqz1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vh-7cqz1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:chart-bar" {...props}></Icon>
