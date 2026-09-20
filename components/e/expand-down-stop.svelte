<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w99tz1j_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w99tz1j_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:expand-down-stop" {...props}></Icon>
