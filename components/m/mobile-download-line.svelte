<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neebi438u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="neebi438u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mobile-download-line" {...props}></Icon>
