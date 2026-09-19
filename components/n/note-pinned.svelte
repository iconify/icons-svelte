<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqae2nbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hqae2nbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:note-pinned" {...props}></Icon>
