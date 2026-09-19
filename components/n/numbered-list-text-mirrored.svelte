<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zafa9olsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zafa9olsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:numbered-list-text-mirrored" {...props}></Icon>
