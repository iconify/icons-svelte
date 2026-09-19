<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_4vvvb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="x_4vvvb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cuthere" {...props}></Icon>
