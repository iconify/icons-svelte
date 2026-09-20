<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0bcq7o-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0bcq7o-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bard-line" {...props}></Icon>
