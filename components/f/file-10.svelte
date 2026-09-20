<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j68dxzg3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j68dxzg3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:file-10" {...props}></Icon>
