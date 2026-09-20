<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvuw72kws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvuw72kws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cards" {...props}></Icon>
