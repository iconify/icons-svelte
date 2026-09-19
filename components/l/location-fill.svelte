<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd0x-741h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dd0x-741h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:location-fill" {...props}></Icon>
