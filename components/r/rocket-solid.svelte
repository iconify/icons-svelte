<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no6glm4ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="no6glm4ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:rocket-solid" {...props}></Icon>
