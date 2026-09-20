<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz1eobnak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz1eobnak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:customer-service-2-line" {...props}></Icon>
