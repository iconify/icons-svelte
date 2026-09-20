<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl5l6ibkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hl5l6ibkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ethernet" {...props}></Icon>
