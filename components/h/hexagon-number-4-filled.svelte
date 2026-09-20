<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5cgm049q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5cgm049q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-number-4-filled" {...props}></Icon>
