<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laa7w7bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="laa7w7bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:facebook-oval" {...props}></Icon>
