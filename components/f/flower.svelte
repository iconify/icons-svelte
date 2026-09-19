<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0g4ab6vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="o0g4ab6vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:flower" {...props}></Icon>
