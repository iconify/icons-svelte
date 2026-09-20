<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfkk76bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfkk76bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:call-outgoing-filled" {...props}></Icon>
