<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj38nmb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj38nmb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-mobile-dollar" {...props}></Icon>
