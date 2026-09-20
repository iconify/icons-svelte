<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sln4qdbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sln4qdbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:captions-off" {...props}></Icon>
