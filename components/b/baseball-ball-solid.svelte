<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s23gm2xlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s23gm2xlw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:baseball-ball-solid" {...props}></Icon>
