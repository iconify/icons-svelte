<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg-cnbbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wg-cnbbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:polygonal-lasso-tool-solid" {...props}></Icon>
