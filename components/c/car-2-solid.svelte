<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcus68cnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gcus68cnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:car-2-solid" {...props}></Icon>
