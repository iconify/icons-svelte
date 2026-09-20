<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nigbbacpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nigbbacpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-enhance-outline" {...props}></Icon>
