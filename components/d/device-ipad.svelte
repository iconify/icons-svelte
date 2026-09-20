<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3nd6zn0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3nd6zn0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad" {...props}></Icon>
