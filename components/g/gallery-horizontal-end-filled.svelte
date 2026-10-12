<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y79pc66rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y79pc66rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:gallery-horizontal-end-filled" {...props}></Icon>
