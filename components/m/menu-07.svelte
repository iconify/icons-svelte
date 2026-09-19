<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzl52293y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzl52293y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:menu-07" {...props}></Icon>
