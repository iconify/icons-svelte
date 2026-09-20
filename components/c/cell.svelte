<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isf2-mbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isf2-mbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cell" {...props}></Icon>
