<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh7iqib0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh7iqib0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hash-bulk-round" {...props}></Icon>
