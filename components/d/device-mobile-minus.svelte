<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjd3gubjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjd3gubjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-mobile-minus" {...props}></Icon>
