<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhonq9zgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zhonq9zgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chromium-light" {...props}></Icon>
