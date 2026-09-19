<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erpo1w27n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erpo1w27n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:bookmark-outline" {...props}></Icon>
