<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w97go_krl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="w97go_krl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:cloud" {...props}></Icon>
