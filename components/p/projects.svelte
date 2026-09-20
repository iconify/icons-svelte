<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypo4zjzwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ypo4zjzwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:projects" {...props}></Icon>
