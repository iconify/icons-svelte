<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_fiq-zyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":769,"height":1024};
const content = `<path class="b_fiq-zyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:microscope" {...props}></Icon>
