<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgcm3wb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgcm3wb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dotted-letter-w" {...props}></Icon>
