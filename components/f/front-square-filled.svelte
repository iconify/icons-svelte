<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fflkcy2nb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fflkcy2nb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:front-square-filled" {...props}></Icon>
