<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjvb-7nsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjvb-7nsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:location-1-filled" {...props}></Icon>
