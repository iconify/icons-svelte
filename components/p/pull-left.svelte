<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_uf0fb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="h_uf0fb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:pull-left" {...props}></Icon>
