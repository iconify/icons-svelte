<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f932xy51a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f932xy51a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ratio-16-9-bulk-round" {...props}></Icon>
