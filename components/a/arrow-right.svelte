<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmdw-9bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="xmdw-9bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:arrow-right" {...props}></Icon>
