<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn97v2brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hn97v2brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:pen" {...props}></Icon>
