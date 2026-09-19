<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjven60rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zjven60rw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:five-of-circles-mahjong-filled" {...props}></Icon>
