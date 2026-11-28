<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqre4nbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqre4nbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:message-square-search" {...props}></Icon>
