<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt61bkbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="jt61bkbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:repeat" {...props}></Icon>
