<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn8q6pbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qn8q6pbgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-bar-up" {...props}></Icon>
