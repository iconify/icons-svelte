<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-802rbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z-802rbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:hierarchy-1-solid" {...props}></Icon>
