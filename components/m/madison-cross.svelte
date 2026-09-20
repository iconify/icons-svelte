<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmzvwc6ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rmzvwc6ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:madison-cross" {...props}></Icon>
