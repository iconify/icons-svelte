<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk2h56bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="rk2h56bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:coffee" {...props}></Icon>
