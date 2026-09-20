<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9kqq8b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r9kqq8b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crt-sh-light" {...props}></Icon>
