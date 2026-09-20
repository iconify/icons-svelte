<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxnmjyt7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxnmjyt7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:live-location-fill" {...props}></Icon>
