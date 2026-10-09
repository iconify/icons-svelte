<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az1dy05bx.css';
import '../../css/d/d6eot3bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="az1dy05bx"/><path class="d6eot3bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-up-right-20-bold" {...props}></Icon>
