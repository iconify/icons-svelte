<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpkk2ibpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpkk2ibpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:map-pin-5-fill" {...props}></Icon>
