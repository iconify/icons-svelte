<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjk_9gmia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bjk_9gmia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:play" {...props}></Icon>
