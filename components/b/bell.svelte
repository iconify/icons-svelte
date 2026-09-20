<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w20l3vtqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="w20l3vtqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:bell" {...props}></Icon>
