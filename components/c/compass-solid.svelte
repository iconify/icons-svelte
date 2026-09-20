<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd6zpubfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xd6zpubfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:compass-solid" {...props}></Icon>
