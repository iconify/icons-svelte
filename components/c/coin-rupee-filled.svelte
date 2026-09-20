<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgl4bwb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgl4bwb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:coin-rupee-filled" {...props}></Icon>
