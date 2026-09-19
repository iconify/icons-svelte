<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke08gvjmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke08gvjmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ram-memory" {...props}></Icon>
