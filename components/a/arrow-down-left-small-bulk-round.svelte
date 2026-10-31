<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkzb6vbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkzb6vbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-down-left-small-bulk-round" {...props}></Icon>
