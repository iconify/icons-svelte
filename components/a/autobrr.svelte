<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl1lzyb4w.css';
import '../../css/l/l3fjs4bnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yl1lzyb4w"/><path class="l3fjs4bnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:autobrr" {...props}></Icon>
