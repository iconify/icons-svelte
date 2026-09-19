<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r61xc-b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":318,"height":512};
const content = `<path class="r61xc-b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:owl" {...props}></Icon>
