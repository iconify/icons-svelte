<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq27p9txl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yq27p9txl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:addydotio" {...props}></Icon>
