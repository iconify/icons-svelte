<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkzxjjbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkzxjjbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-circle-x" {...props}></Icon>
