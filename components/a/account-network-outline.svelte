<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aop-n-4fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aop-n-4fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-network-outline" {...props}></Icon>
