<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrqsnub8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="lrqsnub8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:file-c-s-s" {...props}></Icon>
