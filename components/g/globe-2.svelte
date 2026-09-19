<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6y23s48j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="j6y23s48j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:globe-2" {...props}></Icon>
