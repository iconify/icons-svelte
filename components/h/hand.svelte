<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjuinsb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sjuinsb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:hand" {...props}></Icon>
