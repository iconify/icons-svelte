<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llqv21b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llqv21b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:face-tongue-outline" {...props}></Icon>
