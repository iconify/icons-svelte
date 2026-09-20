<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbtc7xbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kbtc7xbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:n8n" {...props}></Icon>
