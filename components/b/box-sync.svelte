<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws3eji2la.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws3eji2la"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-sync" {...props}></Icon>
