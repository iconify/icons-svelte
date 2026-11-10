<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmn17dblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xmn17dblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bookmark-x-mark-20-solid" {...props}></Icon>
