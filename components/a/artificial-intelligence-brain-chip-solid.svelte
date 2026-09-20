<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/belk3o3_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="belk3o3_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:artificial-intelligence-brain-chip-solid" {...props}></Icon>
