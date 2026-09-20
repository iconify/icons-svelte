<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbi57gbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wbi57gbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:archive-box-solid" {...props}></Icon>
