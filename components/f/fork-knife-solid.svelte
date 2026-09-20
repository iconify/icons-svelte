<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqi_j-b4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wqi_j-b4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:fork-knife-solid" {...props}></Icon>
