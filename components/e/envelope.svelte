<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgs0yzbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xgs0yzbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:envelope" {...props}></Icon>
