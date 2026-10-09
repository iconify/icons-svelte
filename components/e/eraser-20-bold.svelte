<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbr1c2bcx.css';
import '../../css/b/b-mh2-9jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hbr1c2bcx"/><path class="b-mh2-9jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:eraser-20-bold" {...props}></Icon>
