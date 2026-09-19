<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpbo3xbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpbo3xbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:circle-arrow-out-down-right" {...props}></Icon>
