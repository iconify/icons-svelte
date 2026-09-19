<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra9atrb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ra9atrb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-bmp" {...props}></Icon>
