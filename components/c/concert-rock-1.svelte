<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9uztebva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9uztebva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:concert-rock-1" {...props}></Icon>
