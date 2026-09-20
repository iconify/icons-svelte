<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4p_t1bdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i4p_t1bdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coughing-face-in-circle" {...props}></Icon>
