<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s68f012ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s68f012ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-edit-outline" {...props}></Icon>
