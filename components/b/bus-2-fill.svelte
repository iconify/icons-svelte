<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5mkv68pk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5mkv68pk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bus-2-fill" {...props}></Icon>
