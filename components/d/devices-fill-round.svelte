<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udd7sr0oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udd7sr0oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:devices-fill-round" {...props}></Icon>
