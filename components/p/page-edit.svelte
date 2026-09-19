<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5lzyde5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g5lzyde5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:page-edit" {...props}></Icon>
