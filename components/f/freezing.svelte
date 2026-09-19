<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn2gz5idw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xn2gz5idw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:freezing" {...props}></Icon>
