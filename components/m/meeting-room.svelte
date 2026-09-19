<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq-ey0bqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tq-ey0bqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:meeting-room" {...props}></Icon>
