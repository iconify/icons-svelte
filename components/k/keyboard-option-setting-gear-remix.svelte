<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yms-1bcdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yms-1bcdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:keyboard-option-setting-gear-remix" {...props}></Icon>
