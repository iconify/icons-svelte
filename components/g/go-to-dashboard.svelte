<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixa7405ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ixa7405ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:go-to-dashboard" {...props}></Icon>
