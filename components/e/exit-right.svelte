<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1sz4ix2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="z1sz4ix2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:exit-right" {...props}></Icon>
