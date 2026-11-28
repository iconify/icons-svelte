<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp7ogdeoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wp7ogdeoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:playlist-plus" {...props}></Icon>
