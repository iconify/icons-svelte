<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apgajm5hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="apgajm5hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:account-box-mail" {...props}></Icon>
