<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxdhj7bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxdhj7bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:indent-solid" {...props}></Icon>
