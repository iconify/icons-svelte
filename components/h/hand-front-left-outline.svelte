<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib1by3zrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ib1by3zrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-front-left-outline" {...props}></Icon>
