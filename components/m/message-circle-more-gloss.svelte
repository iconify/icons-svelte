<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu8lg6sbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu8lg6sbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-circle-more-gloss" {...props}></Icon>
