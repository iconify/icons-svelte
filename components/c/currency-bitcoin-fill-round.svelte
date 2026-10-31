<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0wg_qb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0wg_qb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:currency-bitcoin-fill-round" {...props}></Icon>
