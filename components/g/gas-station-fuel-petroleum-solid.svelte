<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfdgs3bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xfdgs3bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:gas-station-fuel-petroleum-solid" {...props}></Icon>
