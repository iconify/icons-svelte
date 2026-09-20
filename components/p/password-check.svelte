<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm0--3b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm0--3b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:password-check" {...props}></Icon>
