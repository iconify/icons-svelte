<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flrbi8fuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="flrbi8fuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:computer-exclamation-filled" {...props}></Icon>
