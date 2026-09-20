<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2433jojn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2433jojn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-refresh-outline" {...props}></Icon>
