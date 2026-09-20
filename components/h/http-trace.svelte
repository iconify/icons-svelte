<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtqlo9dtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtqlo9dtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:http-trace" {...props}></Icon>
