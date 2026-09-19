<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5_t2bzyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="a5_t2bzyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:road" {...props}></Icon>
