<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc7r4x4eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc7r4x4eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:book-line" {...props}></Icon>
