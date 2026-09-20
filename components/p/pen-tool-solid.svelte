<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0n8p_5eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z0n8p_5eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pen-tool-solid" {...props}></Icon>
