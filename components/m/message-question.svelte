<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc39y9b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc39y9b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-question" {...props}></Icon>
