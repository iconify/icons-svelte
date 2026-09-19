<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo7pg_b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jo7pg_b1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:account-activity" {...props}></Icon>
