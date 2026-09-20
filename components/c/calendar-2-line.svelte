<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fegcqpb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fegcqpb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:calendar-2-line" {...props}></Icon>
