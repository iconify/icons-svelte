<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2r1s-rsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2r1s-rsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cursor-target-1-bold" {...props}></Icon>
