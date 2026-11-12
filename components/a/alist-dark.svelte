<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw4lhncak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xw4lhncak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alist-dark" {...props}></Icon>
