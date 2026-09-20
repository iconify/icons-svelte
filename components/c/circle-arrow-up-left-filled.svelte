<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mibaxvb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mibaxvb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-arrow-up-left-filled" {...props}></Icon>
