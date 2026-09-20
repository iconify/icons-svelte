<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn5b9sbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="fn5b9sbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:comment-alt-filled" {...props}></Icon>
