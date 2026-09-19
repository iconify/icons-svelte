<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhm0ndz3m.css';
import '../../css/v/vw4ng7gqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yhm0ndz3m"/><path class="vw4ng7gqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:chevron-double-down" {...props}></Icon>
