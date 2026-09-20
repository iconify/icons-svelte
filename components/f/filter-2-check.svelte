<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcmjopvuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcmjopvuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-2-check" {...props}></Icon>
