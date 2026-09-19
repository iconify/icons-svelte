<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8379lkep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="h8379lkep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:eject" {...props}></Icon>
