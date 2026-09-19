<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcs10w16x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="lcs10w16x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:peace" {...props}></Icon>
