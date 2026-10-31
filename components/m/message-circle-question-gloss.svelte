<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aatmnibqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aatmnibqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-circle-question-gloss" {...props}></Icon>
