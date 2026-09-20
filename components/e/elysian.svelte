<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg9of2bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wg9of2bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:elysian" {...props}></Icon>
