<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp1cej1ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp1cej1ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:apple-gloss" {...props}></Icon>
