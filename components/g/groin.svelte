<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gehq5_fws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gehq5_fws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:groin" {...props}></Icon>
