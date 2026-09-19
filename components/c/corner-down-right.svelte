<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_u45qbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_u45qbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:corner-down-right" {...props}></Icon>
