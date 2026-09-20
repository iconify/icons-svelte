<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oly_4rbgm.css';
import '../../css/s/steyv6bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oly_4rbgm"/><path class="steyv6bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:playstation" {...props}></Icon>
