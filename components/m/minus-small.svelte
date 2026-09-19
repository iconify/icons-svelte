<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuv7dvbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zuv7dvbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:minus-small" {...props}></Icon>
