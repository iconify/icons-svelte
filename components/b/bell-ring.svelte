<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8o7mec2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8o7mec2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bell-ring" {...props}></Icon>
