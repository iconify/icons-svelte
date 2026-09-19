<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wys_fmb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wys_fmb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:coursera" {...props}></Icon>
