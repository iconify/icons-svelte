<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9vvm_wmz.css';
import '../../css/z/zpxidp81t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9vvm_wmz"/><path class="zpxidp81t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:graph-bar-vertical-24" {...props}></Icon>
