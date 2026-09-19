<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be24w8bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="be24w8bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:file-system" {...props}></Icon>
