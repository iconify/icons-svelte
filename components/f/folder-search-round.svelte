<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud6q_xb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ud6q_xb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-search-round" {...props}></Icon>
