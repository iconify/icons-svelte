<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk326jbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bk326jbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:list-sparkle-fill-20" {...props}></Icon>
