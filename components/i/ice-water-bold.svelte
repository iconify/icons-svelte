<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuq_gnxqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuq_gnxqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:ice-water-bold" {...props}></Icon>
