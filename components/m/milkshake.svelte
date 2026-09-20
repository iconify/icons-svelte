<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruwtz7ztn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruwtz7ztn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:milkshake" {...props}></Icon>
