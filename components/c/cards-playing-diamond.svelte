<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixbt-153a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixbt-153a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cards-playing-diamond" {...props}></Icon>
