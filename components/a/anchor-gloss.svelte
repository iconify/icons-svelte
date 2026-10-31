<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpoqvibjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpoqvibjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:anchor-gloss" {...props}></Icon>
