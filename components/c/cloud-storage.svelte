<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsdkdebxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsdkdebxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:cloud-storage" {...props}></Icon>
