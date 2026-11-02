<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynm3t7yqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynm3t7yqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-square-share-fill" {...props}></Icon>
