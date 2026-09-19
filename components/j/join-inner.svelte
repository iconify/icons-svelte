<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiu53hmpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aiu53hmpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:join-inner" {...props}></Icon>
