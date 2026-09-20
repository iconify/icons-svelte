<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgel_fcqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bgel_fcqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-flip-left-alternate-1-flip-left-object-work" {...props}></Icon>
