<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2lx_obiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o2lx_obiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:guyed-mast" {...props}></Icon>
