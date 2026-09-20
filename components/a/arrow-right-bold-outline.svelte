<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6t9qrb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6t9qrb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-right-bold-outline" {...props}></Icon>
