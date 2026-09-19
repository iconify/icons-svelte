<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adsuwkqyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adsuwkqyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moustache-filled" {...props}></Icon>
