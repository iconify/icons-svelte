<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb2c8cbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hb2c8cbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:fingerprint-2-fill" {...props}></Icon>
