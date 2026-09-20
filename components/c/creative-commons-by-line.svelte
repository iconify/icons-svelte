<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u06v9hc2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u06v9hc2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:creative-commons-by-line" {...props}></Icon>
