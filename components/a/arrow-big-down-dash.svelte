<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3fz9hbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3fz9hbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-big-down-dash" {...props}></Icon>
