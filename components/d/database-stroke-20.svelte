<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbwrax-_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xbwrax-_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:database-stroke-20" {...props}></Icon>
