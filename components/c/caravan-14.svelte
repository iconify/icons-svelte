<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ums5bfkpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ums5bfkpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:caravan-14" {...props}></Icon>
