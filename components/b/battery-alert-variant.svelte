<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-cceod0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-cceod0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-alert-variant" {...props}></Icon>
