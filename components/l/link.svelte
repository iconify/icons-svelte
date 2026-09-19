<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5-cm9x3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5-cm9x3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:link" {...props}></Icon>
