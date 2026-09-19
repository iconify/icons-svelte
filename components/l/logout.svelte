<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi0-5pbvt.css';
import '../../css/z/z6nnhfbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bi0-5pbvt"/><path class="z6nnhfbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logout" {...props}></Icon>
