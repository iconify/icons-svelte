<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bruc2q60i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bruc2q60i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-circle-heart-gloss" {...props}></Icon>
