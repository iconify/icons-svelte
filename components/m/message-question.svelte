<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxncsqypn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxncsqypn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-question" {...props}></Icon>
