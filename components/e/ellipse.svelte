<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py1-58bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py1-58bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ellipse" {...props}></Icon>
