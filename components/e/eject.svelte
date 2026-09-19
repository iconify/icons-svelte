<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrrg-zbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrrg-zbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:eject" {...props}></Icon>
