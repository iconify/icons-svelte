<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beg4g-64e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beg4g-64e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:list-view" {...props}></Icon>
