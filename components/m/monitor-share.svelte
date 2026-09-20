<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgkmlpr8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgkmlpr8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:monitor-share" {...props}></Icon>
