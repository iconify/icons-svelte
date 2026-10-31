<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z08gxnbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z08gxnbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:glasses-gloss" {...props}></Icon>
