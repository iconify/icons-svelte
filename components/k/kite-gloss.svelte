<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmx4v4cbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmx4v4cbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:kite-gloss" {...props}></Icon>
