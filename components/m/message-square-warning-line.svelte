<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6cb_bcgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6cb_bcgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-square-warning-line" {...props}></Icon>
