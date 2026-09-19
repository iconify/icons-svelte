<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq7lwhbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kq7lwhbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:arlo-cam" {...props}></Icon>
