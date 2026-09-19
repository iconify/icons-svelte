<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w09o7tbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1179,"height":1000};
const content = `<path class="w09o7tbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:chat" {...props}></Icon>
