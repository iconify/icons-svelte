<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpgql3bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dpgql3bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:location-pin-money-atm-1-remix" {...props}></Icon>
