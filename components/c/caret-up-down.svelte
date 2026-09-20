<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spd8p2yvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spd8p2yvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:caret-up-down" {...props}></Icon>
