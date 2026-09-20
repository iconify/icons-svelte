<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fas1yfbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fas1yfbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ironing-off" {...props}></Icon>
