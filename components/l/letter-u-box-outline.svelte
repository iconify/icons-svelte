<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoj2oy0oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aoj2oy0oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-u-box-outline" {...props}></Icon>
