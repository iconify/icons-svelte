<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efaw91i4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="efaw91i4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beephotos-light" {...props}></Icon>
