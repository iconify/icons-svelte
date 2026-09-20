<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afg6-l8sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afg6-l8sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:helicopter" {...props}></Icon>
