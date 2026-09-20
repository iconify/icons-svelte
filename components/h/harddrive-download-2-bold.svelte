<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on9ac8b4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on9ac8b4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:harddrive-download-2-bold" {...props}></Icon>
