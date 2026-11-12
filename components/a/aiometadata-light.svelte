<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd5ezhnwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xd5ezhnwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aiometadata-light" {...props}></Icon>
