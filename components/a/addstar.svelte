<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxke6-btq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":621};
const content = `<path class="xxke6-btq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:addstar" {...props}></Icon>
