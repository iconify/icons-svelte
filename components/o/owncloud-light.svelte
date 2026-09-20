<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y57y3vb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y57y3vb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:owncloud-light" {...props}></Icon>
