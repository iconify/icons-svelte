<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3u6w5bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o3u6w5bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:party-popper-solid" {...props}></Icon>
