<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzxrv2nrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzxrv2nrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-sub-up-left" {...props}></Icon>
