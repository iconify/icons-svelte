<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryv3btb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryv3btb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:files" {...props}></Icon>
