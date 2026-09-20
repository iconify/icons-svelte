<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfh3jn-hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfh3jn-hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-scan-outline" {...props}></Icon>
