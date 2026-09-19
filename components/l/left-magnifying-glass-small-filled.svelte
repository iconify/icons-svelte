<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsjkxfbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wsjkxfbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:left-magnifying-glass-small-filled" {...props}></Icon>
