<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow11ylbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ow11ylbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cooking-pot-gloss" {...props}></Icon>
