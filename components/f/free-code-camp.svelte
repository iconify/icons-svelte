<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byi38ackq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1600};
const content = `<path class="byi38ackq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:free-code-camp" {...props}></Icon>
