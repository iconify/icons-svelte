<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdh19hmax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gdh19hmax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ghostboard-light" {...props}></Icon>
