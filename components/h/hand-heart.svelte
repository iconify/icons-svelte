<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r51emdbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r51emdbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-heart" {...props}></Icon>
