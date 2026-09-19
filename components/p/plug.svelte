<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1bdz0_nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m1bdz0_nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:plug" {...props}></Icon>
