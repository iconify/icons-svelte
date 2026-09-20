<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muno4tb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muno4tb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-letter-e-filled" {...props}></Icon>
