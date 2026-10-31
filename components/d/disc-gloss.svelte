<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocxk99brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocxk99brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:disc-gloss" {...props}></Icon>
