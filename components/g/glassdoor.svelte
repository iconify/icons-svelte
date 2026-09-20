<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urr_ni9ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urr_ni9ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:glassdoor" {...props}></Icon>
