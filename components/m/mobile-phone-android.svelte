<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oum9p75_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oum9p75_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mobile-phone-android" {...props}></Icon>
