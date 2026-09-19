<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m75jywxio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m75jywxio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:custom-list-mirrored" {...props}></Icon>
