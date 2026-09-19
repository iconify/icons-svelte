<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jliq_xbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="jliq_xbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:comment" {...props}></Icon>
