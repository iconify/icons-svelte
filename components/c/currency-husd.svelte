<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-6_nfb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-6_nfb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-husd" {...props}></Icon>
