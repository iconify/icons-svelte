<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcw13cbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gcw13cbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:button-power-circle-1-solid" {...props}></Icon>
