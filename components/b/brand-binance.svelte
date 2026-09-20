<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4x099b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4x099b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-binance" {...props}></Icon>
