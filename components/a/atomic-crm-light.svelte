<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa_y8xbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xa_y8xbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:atomic-crm-light" {...props}></Icon>
