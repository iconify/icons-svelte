<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd3cd6ubq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qd3cd6ubq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:arrow-right" {...props}></Icon>
