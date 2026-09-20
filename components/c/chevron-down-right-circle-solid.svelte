<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb0ktbb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb0ktbb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-down-right-circle-solid" {...props}></Icon>
