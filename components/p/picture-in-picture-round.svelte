<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdqj9mbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdqj9mbyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:picture-in-picture-round" {...props}></Icon>
