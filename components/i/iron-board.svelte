<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar1kdeb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar1kdeb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:iron-board" {...props}></Icon>
