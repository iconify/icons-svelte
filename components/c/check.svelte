<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6ek9acdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="c6ek9acdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:check" {...props}></Icon>
