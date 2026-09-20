<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh5nprbqb.css';
import '../../css/r/rcnhk0biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zh5nprbqb"/><path class="rcnhk0biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pomerium-dark" {...props}></Icon>
