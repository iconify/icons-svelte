<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8jf6yr1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y8jf6yr1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-outlook-2018-light" {...props}></Icon>
