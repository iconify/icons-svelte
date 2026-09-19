<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de14d4b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="de14d4b6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:return-key" {...props}></Icon>
