<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v907xfxmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v907xfxmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:gas-station-fuel-petroleum-solid" {...props}></Icon>
