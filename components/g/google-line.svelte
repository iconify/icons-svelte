<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sciqm6oqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sciqm6oqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:google-line" {...props}></Icon>
