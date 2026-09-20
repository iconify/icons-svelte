<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypi9hb3rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ypi9hb3rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:neutral-face" {...props}></Icon>
