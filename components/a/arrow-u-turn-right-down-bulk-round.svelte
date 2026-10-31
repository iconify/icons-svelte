<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkqathb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkqathb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-u-turn-right-down-bulk-round" {...props}></Icon>
