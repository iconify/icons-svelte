<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyd8mfyoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyd8mfyoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:link-external" {...props}></Icon>
