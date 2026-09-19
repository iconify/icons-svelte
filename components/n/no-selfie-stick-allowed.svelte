<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wul82ibrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wul82ibrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:no-selfie-stick-allowed" {...props}></Icon>
