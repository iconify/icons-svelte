<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlukypb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlukypb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-rain-fill-round" {...props}></Icon>
