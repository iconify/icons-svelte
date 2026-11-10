<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0ysopb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p0ysopb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:folder-x-mark-16-solid" {...props}></Icon>
