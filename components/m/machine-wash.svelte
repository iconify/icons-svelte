<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4cw9ebxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":448};
const content = `<path class="w4cw9ebxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:machine-wash" {...props}></Icon>
