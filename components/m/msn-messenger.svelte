<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2x85_bqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":464};
const content = `<path class="v2x85_bqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:msn-messenger" {...props}></Icon>
