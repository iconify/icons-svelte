<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-80nob0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="a-80nob0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:ftp" {...props}></Icon>
