<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydxj9ob5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ydxj9ob5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-dreamweaver-light" {...props}></Icon>
