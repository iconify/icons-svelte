<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8i-aqr8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="l8i-aqr8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:compsition-horizontal" {...props}></Icon>
