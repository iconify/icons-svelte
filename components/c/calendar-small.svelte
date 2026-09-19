<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcdmvd9fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xcdmvd9fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:calendar-small" {...props}></Icon>
