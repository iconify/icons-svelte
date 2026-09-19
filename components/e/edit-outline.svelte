<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfz7cxbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfz7cxbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:edit-outline" {...props}></Icon>
