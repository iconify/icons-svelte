<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmfqr_b9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmfqr_b9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bitcoin-graph" {...props}></Icon>
