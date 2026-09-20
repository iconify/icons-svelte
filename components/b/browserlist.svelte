<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l11fmibpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":140,"height":140};
const content = `<path class="l11fmibpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:browserlist" {...props}></Icon>
