<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdlc0mnrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mdlc0mnrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:elm-16" {...props}></Icon>
