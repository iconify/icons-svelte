<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm6di3box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="vm6di3box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-alt-waning-gibbous-3" {...props}></Icon>
