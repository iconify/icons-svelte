<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb31-2bss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sb31-2bss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:emoji-neutral" {...props}></Icon>
