<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dku49ip6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dku49ip6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:open-source" {...props}></Icon>
