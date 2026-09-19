<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_6nx47vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="f_6nx47vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bar-chart-horizontal" {...props}></Icon>
