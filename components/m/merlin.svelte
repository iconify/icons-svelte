<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rht3leb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":281.25,"height":281.25};
const content = `<path class="rht3leb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:merlin" {...props}></Icon>
