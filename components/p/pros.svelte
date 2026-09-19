<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkf-omo-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wkf-omo-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:pros" {...props}></Icon>
