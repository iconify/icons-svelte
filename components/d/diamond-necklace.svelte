<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu8i68brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xu8i68brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:diamond-necklace" {...props}></Icon>
