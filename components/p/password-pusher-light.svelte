<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e69it0bqa.css';
import '../../css/a/ad76n-bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e69it0bqa"/><path class="ad76n-bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:password-pusher-light" {...props}></Icon>
