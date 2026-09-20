<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usm1lbbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="usm1lbbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:battery-0-solid" {...props}></Icon>
