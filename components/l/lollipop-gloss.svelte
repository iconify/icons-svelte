<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wasdvd6ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wasdvd6ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lollipop-gloss" {...props}></Icon>
