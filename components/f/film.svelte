<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np3_u8p3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="np3_u8p3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:film" {...props}></Icon>
