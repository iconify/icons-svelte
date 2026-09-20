<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th0kx1-kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="th0kx1-kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:file-jpg" {...props}></Icon>
