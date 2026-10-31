<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s297ernat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s297ernat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-minus-round" {...props}></Icon>
