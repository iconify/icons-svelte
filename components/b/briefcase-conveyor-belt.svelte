<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2zc74r4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2zc74r4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:briefcase-conveyor-belt" {...props}></Icon>
