<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w02dggg3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w02dggg3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:edit-off-03" {...props}></Icon>
