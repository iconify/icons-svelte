<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpz__0blq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpz__0blq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mushroom-gloss" {...props}></Icon>
