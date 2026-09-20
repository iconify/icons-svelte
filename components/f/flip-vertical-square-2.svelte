<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns1pa3bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ns1pa3bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:flip-vertical-square-2" {...props}></Icon>
