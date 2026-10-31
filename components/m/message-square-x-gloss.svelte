<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub-ef1b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub-ef1b8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-square-x-gloss" {...props}></Icon>
