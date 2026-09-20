<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqxhezb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rqxhezb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:aliexpress" {...props}></Icon>
