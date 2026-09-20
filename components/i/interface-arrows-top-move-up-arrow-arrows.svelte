<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfbx2hb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bfbx2hb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-top-move-up-arrow-arrows" {...props}></Icon>
