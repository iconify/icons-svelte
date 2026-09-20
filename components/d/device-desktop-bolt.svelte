<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2m50rcmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2m50rcmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-desktop-bolt" {...props}></Icon>
