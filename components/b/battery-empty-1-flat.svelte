<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv6ya1rlm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jv6ya1rlm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:battery-empty-1-flat" {...props}></Icon>
