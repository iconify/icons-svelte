<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xar84slld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xar84slld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:right-to-left-list-dash" {...props}></Icon>
