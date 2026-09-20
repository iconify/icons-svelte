<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv5chqbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rv5chqbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:magnifying-glass-circle-solid" {...props}></Icon>
