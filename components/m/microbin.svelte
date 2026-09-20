<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eibw0yt8b.css';
import '../../css/v/v45d8qbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eibw0yt8b"/><path class="v45d8qbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microbin" {...props}></Icon>
