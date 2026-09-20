<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5p54cb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5p54cb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:not-protected-outline" {...props}></Icon>
