<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb3z14vnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb3z14vnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:escalator-down-arrow" {...props}></Icon>
