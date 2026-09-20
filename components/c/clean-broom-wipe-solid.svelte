<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbrv5sbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mbrv5sbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:clean-broom-wipe-solid" {...props}></Icon>
