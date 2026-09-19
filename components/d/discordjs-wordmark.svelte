<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm5flfbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zm5flfbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:discordjs-wordmark" {...props}></Icon>
