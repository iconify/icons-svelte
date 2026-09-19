<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybyjabb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ybyjabb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:question-circle" {...props}></Icon>
