<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le1e65bhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="le1e65bhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dolphinsoftware" {...props}></Icon>
