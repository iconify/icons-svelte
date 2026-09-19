<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s08wngb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s08wngb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:cancel" {...props}></Icon>
