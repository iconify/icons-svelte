<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whco19wwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":130};
const content = `<path class="whco19wwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-workspace-wordmark-dark" {...props}></Icon>
