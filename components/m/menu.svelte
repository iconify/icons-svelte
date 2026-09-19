<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoyvg9bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yoyvg9bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:menu" {...props}></Icon>
