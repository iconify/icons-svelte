<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8m5ogb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="y8m5ogb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:rook" {...props}></Icon>
