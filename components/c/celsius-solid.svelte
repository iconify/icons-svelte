<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nub6h3bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nub6h3bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:celsius-solid" {...props}></Icon>
