<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5y088h5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5y088h5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:concert-rock-1-bold" {...props}></Icon>
