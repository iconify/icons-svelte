<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar1aq-_-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar1aq-_-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circle-quarter-filled" {...props}></Icon>
