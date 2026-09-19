<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-56etbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="b-56etbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:hand-right" {...props}></Icon>
