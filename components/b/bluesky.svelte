<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atl1ue-ei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atl1ue-ei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:bluesky" {...props}></Icon>
