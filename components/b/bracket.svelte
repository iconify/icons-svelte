<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd5xxvbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="sd5xxvbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:bracket" {...props}></Icon>
