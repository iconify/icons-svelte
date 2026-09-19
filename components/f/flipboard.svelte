<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7o3m7bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r7o3m7bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:flipboard" {...props}></Icon>
