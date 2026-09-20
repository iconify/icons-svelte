<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4-kmfbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q4-kmfbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:buffer" {...props}></Icon>
