<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk-j6bz5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mk-j6bz5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bulleted-list-2-mirrored" {...props}></Icon>
