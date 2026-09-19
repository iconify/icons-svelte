<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av9zcua6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="av9zcua6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:redo" {...props}></Icon>
