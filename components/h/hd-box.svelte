<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd_g14sid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd_g14sid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hd-box" {...props}></Icon>
