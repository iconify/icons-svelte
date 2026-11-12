<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxiczac0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wxiczac0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alist-light" {...props}></Icon>
