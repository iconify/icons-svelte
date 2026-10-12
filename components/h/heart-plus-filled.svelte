<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1coifbia.css';
import '../../css/s/s6d7cubjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1coifbia"/><path class="s6d7cubjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:heart-plus-filled" {...props}></Icon>
