<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg-_w6iru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xg-_w6iru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:content-writing" {...props}></Icon>
