<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqz1risef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqz1risef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-x-filled" {...props}></Icon>
