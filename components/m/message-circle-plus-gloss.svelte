<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_n748b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_n748b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-circle-plus-gloss" {...props}></Icon>
