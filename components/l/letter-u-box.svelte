<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob3mk329u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob3mk329u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-u-box" {...props}></Icon>
