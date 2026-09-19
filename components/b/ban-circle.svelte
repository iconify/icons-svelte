<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd55nxa0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="cd55nxa0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:ban-circle" {...props}></Icon>
