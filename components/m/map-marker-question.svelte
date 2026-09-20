<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7tvk_bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7tvk_bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:map-marker-question" {...props}></Icon>
