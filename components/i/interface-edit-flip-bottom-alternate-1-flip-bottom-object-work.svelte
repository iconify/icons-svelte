<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v02yasbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="v02yasbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-flip-bottom-alternate-1-flip-bottom-object-work" {...props}></Icon>
