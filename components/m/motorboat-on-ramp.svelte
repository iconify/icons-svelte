<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6t79wbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r6t79wbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorboat-on-ramp" {...props}></Icon>
