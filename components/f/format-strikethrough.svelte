<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxsq7wblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="zxsq7wblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-strikethrough" {...props}></Icon>
