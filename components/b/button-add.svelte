<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fycokac1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="fycokac1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:button-add" {...props}></Icon>
