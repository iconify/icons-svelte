<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyy9ulbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyy9ulbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:calendar-x" {...props}></Icon>
