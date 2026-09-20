<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cujg5k7cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cujg5k7cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:map-down" {...props}></Icon>
