<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao_6u9ujf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao_6u9ujf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter" {...props}></Icon>
