<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyyx4s3jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="qyyx4s3jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-warn-bold" {...props}></Icon>
