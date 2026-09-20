<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whrh0-uol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whrh0-uol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:equal-double" {...props}></Icon>
