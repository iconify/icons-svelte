<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny7p-fz4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ny7p-fz4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:inboxes" {...props}></Icon>
