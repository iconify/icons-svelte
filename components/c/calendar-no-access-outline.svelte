<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2f7d8bkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s2f7d8bkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:calendar-no-access-outline" {...props}></Icon>
