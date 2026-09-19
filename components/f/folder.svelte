<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn3c0xmdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jn3c0xmdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:folder" {...props}></Icon>
