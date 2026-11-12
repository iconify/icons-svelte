<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2a_cniwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l2a_cniwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-tables-light" {...props}></Icon>
