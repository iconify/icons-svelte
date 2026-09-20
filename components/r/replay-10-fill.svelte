<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcupe_3ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcupe_3ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:replay-10-fill" {...props}></Icon>
