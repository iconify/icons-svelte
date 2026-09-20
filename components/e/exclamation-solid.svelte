<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypa0l_ben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ypa0l_ben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:exclamation-solid" {...props}></Icon>
