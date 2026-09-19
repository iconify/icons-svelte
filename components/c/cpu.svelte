<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn5ia6wrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":504};
const content = `<path class="wn5ia6wrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:cpu" {...props}></Icon>
