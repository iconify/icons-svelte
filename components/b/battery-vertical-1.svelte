<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad19tgbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad19tgbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-vertical-1" {...props}></Icon>
