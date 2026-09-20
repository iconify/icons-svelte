<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v79h7tbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v79h7tbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freeshard-dark" {...props}></Icon>
