<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xquo8mb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":961};
const content = `<path class="xquo8mb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:marker" {...props}></Icon>
