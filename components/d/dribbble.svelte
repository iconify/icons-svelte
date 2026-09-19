<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujyzd5b5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ujyzd5b5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:dribbble" {...props}></Icon>
