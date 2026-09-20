<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm1cjwbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="lm1cjwbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:pull-down" {...props}></Icon>
