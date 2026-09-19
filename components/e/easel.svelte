<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns5x1qb3u.css';
import '../../css/c/c-o8u9blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="ns5x1qb3u"/><path class="c-o8u9blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:easel" {...props}></Icon>
