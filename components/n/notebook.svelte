<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4e2zubhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="t4e2zubhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:notebook" {...props}></Icon>
