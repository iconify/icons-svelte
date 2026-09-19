<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu328sq7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zu328sq7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:butter-toast" {...props}></Icon>
