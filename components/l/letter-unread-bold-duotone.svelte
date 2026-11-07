<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjzke8b7e.css';
import '../../css/c/cx6-9bwoj.css';
import '../../css/x/xapju6bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjzke8b7e"/><path class="cx6-9bwoj"/><path class="xapju6bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:letter-unread-bold-duotone" {...props}></Icon>
