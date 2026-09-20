<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkw6nm7zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkw6nm7zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:map-exclamation" {...props}></Icon>
