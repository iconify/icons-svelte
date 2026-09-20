<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcn-j_bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xcn-j_bia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:download-box-1-remix" {...props}></Icon>
