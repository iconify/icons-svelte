<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb8v54b-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yb8v54b-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:align-end-horizontal-filled" {...props}></Icon>
