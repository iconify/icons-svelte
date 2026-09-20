<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbneb4u-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dbneb4u-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-opened-outline" {...props}></Icon>
