<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_0z7bcri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f_0z7bcri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:like-1-solid" {...props}></Icon>
