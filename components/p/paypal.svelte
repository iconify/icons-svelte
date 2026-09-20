<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvtq6p3pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvtq6p3pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:paypal" {...props}></Icon>
