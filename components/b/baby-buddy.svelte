<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxlk2144c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qxlk2144c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:baby-buddy" {...props}></Icon>
