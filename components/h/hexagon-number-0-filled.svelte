<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6lt7bcvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6lt7bcvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-number-0-filled" {...props}></Icon>
