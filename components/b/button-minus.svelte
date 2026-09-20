<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmc0r12qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="tmc0r12qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:button-minus" {...props}></Icon>
