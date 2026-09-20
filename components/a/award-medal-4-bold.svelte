<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycs9x2bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycs9x2bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:award-medal-4-bold" {...props}></Icon>
