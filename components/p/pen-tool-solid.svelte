<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9exrzbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x9exrzbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:pen-tool-solid" {...props}></Icon>
