<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/batsi3o4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="batsi3o4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:align-back-1-solid" {...props}></Icon>
