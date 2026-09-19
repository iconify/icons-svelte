<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e17znrb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e17znrb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:calendar-remove" {...props}></Icon>
