<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr_jcmkbu.css';
import '../../css/k/k589qfbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qr_jcmkbu"/><path clip-rule="evenodd" class="k589qfbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:device-phone-mobile-16-solid" {...props}></Icon>
