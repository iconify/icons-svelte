<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzr16bc8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kzr16bc8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:erase-tool" {...props}></Icon>
