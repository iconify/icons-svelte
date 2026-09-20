<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu2_20dau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="xu2_20dau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:filtering" {...props}></Icon>
