<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt2wz29tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="rt2wz29tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-grin-tears" {...props}></Icon>
