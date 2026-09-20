<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnty1nisa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnty1nisa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-question" {...props}></Icon>
