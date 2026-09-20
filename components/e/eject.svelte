<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf0d24blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf0d24blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:eject" {...props}></Icon>
