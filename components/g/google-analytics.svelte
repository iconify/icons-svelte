<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8_6fabuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8_6fabuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-analytics" {...props}></Icon>
