<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j51b4ob1j.css';
import '../../css/i/ieygd_q0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j51b4ob1j"/><path class="ieygd_q0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:location-alt-2" {...props}></Icon>
