<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itwh__bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="itwh__bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:battery-quarter" {...props}></Icon>
