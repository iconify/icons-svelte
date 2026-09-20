<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iky3mbb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iky3mbb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:moon-foggy-line" {...props}></Icon>
