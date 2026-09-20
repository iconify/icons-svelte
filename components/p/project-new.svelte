<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc2ezlbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rc2ezlbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:project-new" {...props}></Icon>
