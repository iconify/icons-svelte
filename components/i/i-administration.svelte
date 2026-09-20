<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/surq_x5uw.css';
import '../../css/z/z0cv2cc8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="surq_x5uw"/><path class="z0cv2cc8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-administration" {...props}></Icon>
