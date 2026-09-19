<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa19cjbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="oa19cjbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:batteryaltcharging" {...props}></Icon>
