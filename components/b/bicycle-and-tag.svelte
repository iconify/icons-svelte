<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/palcz1bcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="palcz1bcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-and-tag" {...props}></Icon>
