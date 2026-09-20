<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr7zo8bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vr7zo8bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:browser-key-solid" {...props}></Icon>
