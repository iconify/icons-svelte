<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0ikg4bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n0ikg4bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:mobile-phone-camera-solid" {...props}></Icon>
